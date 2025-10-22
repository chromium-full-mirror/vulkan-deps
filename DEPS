# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '5f6c7176c5483da9af6432afb3dd962e4f8873a1',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'cfc58898cb45c60e320ad81e7808823b9b3d8d09',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '9268f3057354a2cb65991ba5f38b16d81e803692',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '1b74d6765d8c02e450518187cfc1efa08ab8dd17',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '33d7f512583b8de44d1b6384aa1cf482f92e53e9',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '66f2ce1f4683231d13e7e0566a83fc65beddaf08',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '17c41541e8e43364af6ccb4a6ce167274152cd7a',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'd80e0dba8525f7bb0c65dec67da68f5f033b3935',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '5d9b124fadebe10576390e1274fd45e033948042',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
