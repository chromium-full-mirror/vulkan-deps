# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '09c541ee5b22bbac307987b50d86ec2b4f683d75',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '5293aca8308eb936048f5149ab7c4a883ae5e63f',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '465055f6c9128772e20082e893d974146acf7a02',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '5d6745bfdd3bdb3a5e04a6016104851244e12cdb',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '29184b98984f6169a5e83e97557a77cff1e5b0ca',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '6923f2b7e869dd94a09dcdd6fa2152269edc7fef',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '59f963ce1b1d16cc92137a241a0fe98d637d21f4',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '56773a2b578bb5831a1d8eb1927cd9ea92dddc65',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '8ac138632faca0027a31849d05423f4914b49f3c',
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
