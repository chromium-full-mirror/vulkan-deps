# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '8a85691a0740d390761a1008b4696f57facd02c4',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '7d17a4c1bc1d631df60f7a5ada7892cf276f4bdd',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '04b76709bf40a7ce8df3382060ef3620f19de566',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '40eb301f320e1d85ce3bc12798022149eae3eee3',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '16cedde3564629c43808401ad1eb3ca6ef24709a',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'eb5baa53c657b89f515429a8e9b2db246f83d341',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '99365fc264be73f264ef2fccc98bfb1a9d3c4592',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'f216bb107bfc6d99a9605572963613e828b10880',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'ad9c5256998a1f57e7f471130d9d624486b6b89c',
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
