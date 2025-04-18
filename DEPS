# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'ba1640446f3826a518721d1f083f3a8cca1120c3',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '1104d6ad976fa118b41b6312521488efad3f004d',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'aa6cef192b8e693916eb713e7a9ccadf06062ceb',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'ca63ea568b41d461dd25fa588350008b5ab00c89',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '110b6c989ccb4e874089db777e2b54eb9abb5670',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'a8513ac9d0e367c5914095d0b7f09a081a14b4b5',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '50ace769d381f746d7d6cb75db982fa4d94a112f',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '4ee0833a3cdb834aa71c2b77ce5b01235b7b7170',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'b8771d6a9b7f9ed2c0f42e33fef2c8edbf2e73cb',
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
